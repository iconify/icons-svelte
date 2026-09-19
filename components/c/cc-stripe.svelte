<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plc38_bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="plc38_bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-stripe" {...props}></Icon>
