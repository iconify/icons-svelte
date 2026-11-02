<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyl-lskto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyl-lskto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-marked-fill" {...props}></Icon>
