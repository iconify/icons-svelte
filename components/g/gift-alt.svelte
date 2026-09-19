<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1fa9fn7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d1fa9fn7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gift-alt" {...props}></Icon>
