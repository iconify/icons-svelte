<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoubbo_e.css';
import '../../css/w/wr4cx4b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="wr4cx4b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-3" {...props}></Icon>
