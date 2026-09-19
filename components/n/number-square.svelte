<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb3519b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xb3519b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:number-square" {...props}></Icon>
