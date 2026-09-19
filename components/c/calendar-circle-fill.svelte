<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrn8-zb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qrn8-zb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:calendar-circle-fill" {...props}></Icon>
