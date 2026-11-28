<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbw81nbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbw81nbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-plus" {...props}></Icon>
