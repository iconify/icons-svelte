<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2c-w6bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="w2c-w6bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:island" {...props}></Icon>
