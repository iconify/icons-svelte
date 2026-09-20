<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yasmpbimd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yasmpbimd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiodeck-dark" {...props}></Icon>
