<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ths1xlbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ths1xlbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:cross-mark" {...props}></Icon>
