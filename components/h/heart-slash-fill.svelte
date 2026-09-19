<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zppi94bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zppi94bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:heart-slash-fill" {...props}></Icon>
