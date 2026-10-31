<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz_4v-slc.css';
import '../../css/t/t9rd-mm-b.css';
import '../../css/a/acbfzvwzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="vz_4v-slc"/><path class="t9rd-mm-b"/><path class="acbfzvwzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:estonia" {...props}></Icon>
