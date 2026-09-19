<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ethcq8boj.css';
import '../../css/s/sit0_i-ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ethcq8boj"/><path class="sit0_i-ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-add" {...props}></Icon>
