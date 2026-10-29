<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkmfunbhg.css';
import '../../css/f/fvf990b7v.css';
import '../../css/t/txskvxb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkmfunbhg wm-a"/><path class="fvf990b7v wm-k"/><path class="txskvxb8d wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:battery-charging" {...props}></Icon>
