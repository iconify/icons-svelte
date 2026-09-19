<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if_6tkb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":720,"height":840};
const content = `<path class="if_6tkb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:layers" {...props}></Icon>
