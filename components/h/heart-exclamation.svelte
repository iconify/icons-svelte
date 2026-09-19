<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8p50493h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k8p50493h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:heart-exclamation" {...props}></Icon>
