<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h14ltnbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h14ltnbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-beaker" {...props}></Icon>
