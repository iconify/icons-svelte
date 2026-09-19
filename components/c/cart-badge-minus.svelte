<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfm31cbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dfm31cbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cart-badge-minus" {...props}></Icon>
