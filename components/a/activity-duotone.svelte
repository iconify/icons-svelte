<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0yuwq6mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y0yuwq6mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:activity-duotone" {...props}></Icon>
