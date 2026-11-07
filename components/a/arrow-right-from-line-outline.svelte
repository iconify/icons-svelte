<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly14d-arz.css';
import '../../css/e/exasy4ryo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly14d-arz"/><path class="exasy4ryo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-from-line-outline" {...props}></Icon>
