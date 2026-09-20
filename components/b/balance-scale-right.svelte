<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op63yotmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="op63yotmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:balance-scale-right" {...props}></Icon>
