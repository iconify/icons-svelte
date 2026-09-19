<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kh3iwjkha.css';
import '../../css/r/r5hrfmbxe.css';
import '../../css/r/rzt6kdb0a.css';
import '../../css/w/wp060k89a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kh3iwjkha"/><path class="r5hrfmbxe"/><path class="rzt6kdb0a"/><path class="wp060k89a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:eye-slash" {...props}></Icon>
