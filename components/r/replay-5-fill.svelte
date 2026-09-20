<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsziz-bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsziz-bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:replay-5-fill" {...props}></Icon>
