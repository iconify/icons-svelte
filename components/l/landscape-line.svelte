<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmd1qmb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmd1qmb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:landscape-line" {...props}></Icon>
