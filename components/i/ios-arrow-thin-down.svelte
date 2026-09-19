<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7_ev5eiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a7_ev5eiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-thin-down" {...props}></Icon>
