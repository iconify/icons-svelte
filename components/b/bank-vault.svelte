<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iux_xg0hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iux_xg0hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bank-vault" {...props}></Icon>
