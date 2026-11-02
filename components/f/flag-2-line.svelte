<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8t7dyboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8t7dyboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-2-line" {...props}></Icon>
