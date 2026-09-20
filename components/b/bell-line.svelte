<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ara_o5b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ara_o5b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bell-line" {...props}></Icon>
