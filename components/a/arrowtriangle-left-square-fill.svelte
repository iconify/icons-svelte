<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de6jlgzhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="de6jlgzhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-left-square-fill" {...props}></Icon>
