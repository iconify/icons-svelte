<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsw-kbb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsw-kbb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brace-left-duo" {...props}></Icon>
