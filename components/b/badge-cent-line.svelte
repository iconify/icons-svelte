<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6c8e7biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6c8e7biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-cent-line" {...props}></Icon>
