<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uio9qibqb.css';
import '../../css/j/jcy41ac7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="uio9qibqb"/><path class="jcy41ac7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:richy" {...props}></Icon>
