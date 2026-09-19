<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xek6uc-xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xek6uc-xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-text-fill" {...props}></Icon>
