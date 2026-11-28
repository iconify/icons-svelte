<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lc5lxb17d.css';
import '../../css/r/rbohgvl9x.css';
import '../../css/u/udm6iph_s.css';
import '../../css/k/ky1-w1byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lc5lxb17d"/><path class="rbohgvl9x"/><path class="udm6iph_s"/><path class="ky1-w1byj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-merge" {...props}></Icon>
