<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_l_77bcd.css';
import '../../css/h/hbryolsnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_l_77bcd"/><path class="hbryolsnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:factory" {...props}></Icon>
