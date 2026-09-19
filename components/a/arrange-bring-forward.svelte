<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au_w-gbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="au_w-gbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrange-bring-forward" {...props}></Icon>
