<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tabif8blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tabif8blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward-45" {...props}></Icon>
