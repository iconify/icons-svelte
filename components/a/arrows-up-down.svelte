<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzqp71q4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqp71q4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrows-up-down" {...props}></Icon>
