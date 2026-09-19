<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz2zk-lcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz2zk-lcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:link-bold" {...props}></Icon>
