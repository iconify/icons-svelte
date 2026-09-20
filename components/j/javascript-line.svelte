<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh9u6ecdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh9u6ecdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:javascript-line" {...props}></Icon>
