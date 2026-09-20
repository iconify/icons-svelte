<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq8x8nbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq8x8nbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:adblock-plus" {...props}></Icon>
