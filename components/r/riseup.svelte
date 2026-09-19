<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpzi36bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpzi36bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:riseup" {...props}></Icon>
