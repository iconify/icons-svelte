<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iclyhyb7e.css';
import '../../css/j/jnkd4081l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iclyhyb7e"/><path class="jnkd4081l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:reply-all" {...props}></Icon>
