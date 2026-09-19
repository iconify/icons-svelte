<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3_nl4dxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="m3_nl4dxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-2" {...props}></Icon>
