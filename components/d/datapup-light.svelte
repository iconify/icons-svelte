<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5yk22b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5yk22b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:datapup-light" {...props}></Icon>
