<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhwhtybel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhwhtybel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:funds-box-line" {...props}></Icon>
