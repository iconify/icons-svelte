<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ignec6b8h.css';
import '../../css/e/edgg_m-zr.css';
import '../../css/e/eyrktq3-q.css';
import '../../css/l/lo6d6knyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ignec6b8h"/><path class="edgg_m-zr"/><path class="eyrktq3-q"/><path class="lo6d6knyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:eritrea" {...props}></Icon>
