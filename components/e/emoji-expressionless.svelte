<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk8vunbuz.css';
import '../../css/j/jb0hwxb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8vunbuz"/><path clip-rule="evenodd" class="jb0hwxb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:emoji-expressionless" {...props}></Icon>
