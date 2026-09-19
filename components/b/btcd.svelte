<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0k77fb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c0k77fb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:btcd" {...props}></Icon>
