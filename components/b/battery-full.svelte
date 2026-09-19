<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ciw2bty.css';
import '../../css/o/otarylbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9ciw2bty"/><path class="otarylbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:battery-full" {...props}></Icon>
