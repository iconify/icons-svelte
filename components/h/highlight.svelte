<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogo0ji8gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogo0ji8gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:highlight" {...props}></Icon>
