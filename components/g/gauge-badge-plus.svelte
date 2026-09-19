<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6d4qmufc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x6d4qmufc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gauge-badge-plus" {...props}></Icon>
