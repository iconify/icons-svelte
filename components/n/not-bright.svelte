<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_lobbbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<circle class="o_lobbbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:not-bright" {...props}></Icon>
