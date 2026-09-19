<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_h1abcbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_h1abcbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:jpy" {...props}></Icon>
