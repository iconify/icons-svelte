<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl010k52n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vl010k52n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bill" {...props}></Icon>
