<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uea3lmbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uea3lmbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:ribbon" {...props}></Icon>
