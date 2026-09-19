<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbeiz5roj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbeiz5roj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-grid-vertical" {...props}></Icon>
