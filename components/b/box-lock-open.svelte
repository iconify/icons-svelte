<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoakzdbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoakzdbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-lock-open" {...props}></Icon>
