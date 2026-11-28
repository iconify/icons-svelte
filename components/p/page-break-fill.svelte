<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twfqpvbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="twfqpvbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:page-break-fill" {...props}></Icon>
