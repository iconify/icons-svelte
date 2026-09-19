<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv6chp-kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv6chp-kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:octagon-filled" {...props}></Icon>
