<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euy7x3bzx.css';
import '../../css/c/c7zalxt4x.css';
import '../../css/l/la19u4bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="euy7x3bzx"/><path class="c7zalxt4x"/><path class="la19u4bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-unknown" {...props}></Icon>
