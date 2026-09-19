<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex8j4trvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ex8j4trvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:circle-righthalf-fill" {...props}></Icon>
