<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpy4_z3jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpy4_z3jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-3-fill" {...props}></Icon>
