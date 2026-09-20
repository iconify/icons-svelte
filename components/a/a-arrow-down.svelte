<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-o_3jm7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-o_3jm7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:a-arrow-down" {...props}></Icon>
