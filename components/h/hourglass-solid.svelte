<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqq99_76y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqq99_76y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hourglass-solid" {...props}></Icon>
