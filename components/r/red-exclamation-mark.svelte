<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku0q42bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ku0q42bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-exclamation-mark" {...props}></Icon>
