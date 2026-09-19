<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugq91db8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ugq91db8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:home-lg" {...props}></Icon>
