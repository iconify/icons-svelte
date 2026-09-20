<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kql4cwbwx.css';
import '../../css/t/td28wmbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kql4cwbwx"/><path class="td28wmbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:product-hunt" {...props}></Icon>
