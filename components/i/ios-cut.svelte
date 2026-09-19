<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbht7_vyu.css';
import '../../css/h/hxw8-dzsl.css';
import '../../css/f/f_pda4xwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tbht7_vyu"/><path class="hxw8-dzsl"/><path class="f_pda4xwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cut" {...props}></Icon>
