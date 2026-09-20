<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce5wpgb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce5wpgb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clubs-line" {...props}></Icon>
