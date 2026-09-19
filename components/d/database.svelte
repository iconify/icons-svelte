<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/q/qg9w3n3bs.css';
import '../../css/s/s8127tbcg.css';
import '../../css/k/k76zracww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="qg9w3n3bs"/><ellipse class="s8127tbcg"/><path class="k76zracww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:database" {...props}></Icon>
