<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycy63pt0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ycy63pt0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:payx" {...props}></Icon>
