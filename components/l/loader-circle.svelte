<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhr2xybsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhr2xybsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:loader-circle" {...props}></Icon>
