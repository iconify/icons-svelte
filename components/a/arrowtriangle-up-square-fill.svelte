<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh2h_7u6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dh2h_7u6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-up-square-fill" {...props}></Icon>
