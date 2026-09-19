<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsnta9bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qsnta9bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-enabled-pdlc" {...props}></Icon>
