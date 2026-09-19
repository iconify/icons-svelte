<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq7mt7e7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dq7mt7e7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:paw-prints" {...props}></Icon>
