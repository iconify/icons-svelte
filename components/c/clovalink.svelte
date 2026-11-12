<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anh9su9vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anh9su9vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clovalink" {...props}></Icon>
