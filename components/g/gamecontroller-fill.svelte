<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-bqyd3sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i-bqyd3sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gamecontroller-fill" {...props}></Icon>
