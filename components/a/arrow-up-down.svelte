<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huyx0gevn.css';
import '../../css/l/lmzjhacao.css';
import '../../css/w/wqefnac-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huyx0gevn"/><path class="lmzjhacao"/><path class="wqefnac-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-up-down" {...props}></Icon>
