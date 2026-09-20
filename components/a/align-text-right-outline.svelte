<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf1a-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="myf1a-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-text-right-outline" {...props}></Icon>
