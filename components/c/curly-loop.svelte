<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et4ql6hmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="et4ql6hmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:curly-loop" {...props}></Icon>
