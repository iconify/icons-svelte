<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mcccz011g.css';
import '../../css/f/fnqnyblgp.css';
import '../../css/l/lzjuftnye.css';
import '../../css/l/laudgkbxt.css';
import '../../css/y/yi1m21xqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mcccz011g"/><path class="fnqnyblgp"/><path class="lzjuftnye"/><path class="laudgkbxt"/><path class="yi1m21xqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:projector" {...props}></Icon>
