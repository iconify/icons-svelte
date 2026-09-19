<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukg496alp.css';
import '../../css/m/m2xavebym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect transform="rotate(-45)" class="ukg496alp"/><path class="m2xavebym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:pre-commit" {...props}></Icon>
