<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8etgtbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="o8etgtbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:at" {...props}></Icon>
