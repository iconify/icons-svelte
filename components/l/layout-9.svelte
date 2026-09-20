<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps15tebrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ps15tebrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:layout-9" {...props}></Icon>
