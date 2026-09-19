<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3_i3uapp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3_i3uapp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:double-curly-loop" {...props}></Icon>
