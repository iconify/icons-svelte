<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoubbo_e.css';
import '../../css/d/d8xx8hb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="d8xx8hb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-2" {...props}></Icon>
