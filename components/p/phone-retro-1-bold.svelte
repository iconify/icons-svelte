<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plcuanbng.css';
import '../../css/j/jx0lkpbqx.css';
import '../../css/a/a4nu-p1co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plcuanbng"/><path class="jx0lkpbqx"/><path class="a4nu-p1co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-retro-1-bold" {...props}></Icon>
