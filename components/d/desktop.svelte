<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnb5ity-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qnb5ity-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:desktop" {...props}></Icon>
