<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upy-ybcph.css';
import '../../css/i/i1e923jjk.css';
import '../../css/z/z54ut_7zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="upy-ybcph"/><path class="i1e923jjk"/><path class="z54ut_7zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-48" {...props}></Icon>
