<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wchz1fbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wchz1fbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bag-badge-minus" {...props}></Icon>
