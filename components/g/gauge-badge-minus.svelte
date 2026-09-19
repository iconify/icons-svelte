<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfjlrq1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fzfjlrq1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gauge-badge-minus" {...props}></Icon>
