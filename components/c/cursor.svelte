<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqp-onbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqp-onbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cursor" {...props}></Icon>
