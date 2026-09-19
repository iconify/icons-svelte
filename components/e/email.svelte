<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruzvz6hmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="ruzvz6hmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:email" {...props}></Icon>
