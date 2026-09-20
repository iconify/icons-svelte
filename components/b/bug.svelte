<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqqctl8ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vqqctl8ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bug" {...props}></Icon>
