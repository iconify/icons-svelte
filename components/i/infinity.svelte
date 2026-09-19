<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhe6ibcui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":614};
const content = `<path class="qhe6ibcui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:infinity" {...props}></Icon>
