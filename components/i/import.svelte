<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo55s0bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jo55s0bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:import" {...props}></Icon>
