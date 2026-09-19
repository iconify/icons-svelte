<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh87dwy8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kh87dwy8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:on-arrow" {...props}></Icon>
