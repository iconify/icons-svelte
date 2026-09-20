<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6m02jbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z6m02jbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komodo-cd-light" {...props}></Icon>
