<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdn6aac2h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ap2vq_ggp.css';
import '../../css/z/z5a-asbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdn6aac2h secondary"/><g class="dt0cm9dhy primary"><path class="ap2vq_ggp"/><path class="z5a-asbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:megaphone-duo" {...props}></Icon>
