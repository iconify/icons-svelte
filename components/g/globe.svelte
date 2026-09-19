<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxugl74-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxugl74-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:globe" {...props}></Icon>
