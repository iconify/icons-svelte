<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5m9fgbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d5m9fgbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-on-clipboard" {...props}></Icon>
