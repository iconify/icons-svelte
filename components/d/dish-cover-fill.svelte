<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96s-oj-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h96s-oj-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dish-cover-fill" {...props}></Icon>
