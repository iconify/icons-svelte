<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-guoyy4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-guoyy4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:aircraft-hot-air-balloon-2-bold" {...props}></Icon>
