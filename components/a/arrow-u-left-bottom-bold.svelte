<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-rxwrbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-rxwrbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-left-bottom-bold" {...props}></Icon>
