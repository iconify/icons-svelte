<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipy5vwtjx.css';
import '../../css/d/d6guelbgt.css';
import '../../css/p/pyhrjesye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipy5vwtjx"/><path clip-rule="evenodd" class="d6guelbgt"/><path class="pyhrjesye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:icp" {...props}></Icon>
