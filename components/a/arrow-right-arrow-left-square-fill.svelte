<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jof-b7b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jof-b7b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-right-arrow-left-square-fill" {...props}></Icon>
