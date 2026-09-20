<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y002-9bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y002-9bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-long-line" {...props}></Icon>
