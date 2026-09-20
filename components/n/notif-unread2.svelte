<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gtwutr3uy.css';
import '../../css/s/s-_ewh-er.css';
import '../../css/c/c4eliccbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gtwutr3uy"/><path clip-rule="evenodd" class="s-_ewh-er"/><path class="c4eliccbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notif-unread2" {...props}></Icon>
