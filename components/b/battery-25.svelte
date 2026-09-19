<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp-udmb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tp-udmb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:battery-25" {...props}></Icon>
