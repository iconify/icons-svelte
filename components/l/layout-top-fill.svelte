<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm8--1bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm8--1bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-top-fill" {...props}></Icon>
