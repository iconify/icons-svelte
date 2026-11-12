<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bggzpxb-r.css';
import '../../css/a/acxb7gn1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bggzpxb-r"/><path class="acxb7gn1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composerize" {...props}></Icon>
