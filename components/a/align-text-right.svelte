<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-qk5zavh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="t-qk5zavh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:align-text-right" {...props}></Icon>
