<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aawif9bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aawif9bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:git-square" {...props}></Icon>
