<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klmhtvbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":555,"height":759};
const content = `<path class="klmhtvbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:numbersign" {...props}></Icon>
