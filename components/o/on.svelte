<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v19gj253m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v19gj253m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:on" {...props}></Icon>
