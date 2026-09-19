<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwoo6cbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pwoo6cbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:double-exclamation-mark" {...props}></Icon>
