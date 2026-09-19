<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewzv9gbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewzv9gbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-outer-dashed-circle" {...props}></Icon>
