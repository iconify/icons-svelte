<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggh9rqprt.css';
import '../../css/z/zee_subyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggh9rqprt"/><path class="zee_subyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-bear-right-02-filled" {...props}></Icon>
