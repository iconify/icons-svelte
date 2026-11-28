<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlznw-a5v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b00ennbgq.css';
import '../../css/d/dbfl50qks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tlznw-a5v"/><g class="dt0cm9dhy primary"><path class="b00ennbgq"/><path class="dbfl50qks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-third-duo" {...props}></Icon>
