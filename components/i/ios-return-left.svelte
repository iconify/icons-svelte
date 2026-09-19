<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulk4puohh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ulk4puohh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-return-left" {...props}></Icon>
