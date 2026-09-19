<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jid_jxb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jid_jxb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:mountains" {...props}></Icon>
