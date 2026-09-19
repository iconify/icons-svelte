<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsjqdebvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wsjqdebvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-right-square-fill" {...props}></Icon>
