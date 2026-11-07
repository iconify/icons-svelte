<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccyzdizjg.css';
import '../../css/b/bfvy_zbha.css';
import '../../css/m/mzfoi9l1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccyzdizjg"/><path class="bfvy_zbha"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-square-outline" {...props}></Icon>
