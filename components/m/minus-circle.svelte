<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4u5kll7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4u5kll7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:minus-circle" {...props}></Icon>
