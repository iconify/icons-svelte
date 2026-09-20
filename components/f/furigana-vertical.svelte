<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv128zbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv128zbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:furigana-vertical" {...props}></Icon>
