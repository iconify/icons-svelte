<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy9o_obok.css';
import '../../css/q/qb8d7ybqw.css';
import '../../css/a/a59as3_kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oy9o_obok"/><path class="qb8d7ybqw"/><path class="a59as3_kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-mailbox" {...props}></Icon>
