<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9_8tiwpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9_8tiwpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matterbridge-dark" {...props}></Icon>
