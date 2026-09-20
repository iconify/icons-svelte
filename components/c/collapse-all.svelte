<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk_861ltb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dk_861ltb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:collapse-all" {...props}></Icon>
