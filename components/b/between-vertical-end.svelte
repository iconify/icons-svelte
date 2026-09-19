<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y22acxb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y22acxb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:between-vertical-end" {...props}></Icon>
