<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl2e97jtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kl2e97jtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:infinity-symbol" {...props}></Icon>
