<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_j186bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_j186bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:money" {...props}></Icon>
