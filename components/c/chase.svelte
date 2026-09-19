<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzngd950t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rzngd950t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:chase" {...props}></Icon>
