<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0hucxhbr.css';
import '../../css/q/q4cmd7h4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0hucxhbr"/><path class="q4cmd7h4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dropdown-line" {...props}></Icon>
