<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8qw21b7i.css';
import '../../css/d/dpo67b6zm.css';
import '../../css/z/z8_5hvbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l8qw21b7i"/><path class="dpo67b6zm"/><path class="z8_5hvbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:color-filter" {...props}></Icon>
