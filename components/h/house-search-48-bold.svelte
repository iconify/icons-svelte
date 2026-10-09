<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxvnz_b5x.css';
import '../../css/w/wqenwibkw.css';
import '../../css/c/cj_ng38-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="wqenwibkw"/><path class="cj_ng38-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-search-48-bold" {...props}></Icon>
