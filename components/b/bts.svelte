<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggjpy_jvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggjpy_jvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bts" {...props}></Icon>
