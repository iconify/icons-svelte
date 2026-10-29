<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14ig-bxz.css';
import '../../css/q/q52rgmb9a.css';
import '../../css/n/n792s6bgk.css';
import '../../css/e/e0na4obrw.css';
import '../../css/p/p9xa7qdil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m14ig-bxz"/><path class="q52rgmb9a"/><path class="n792s6bgk"/><path class="e0na4obrw"/><path class="p9xa7qdil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:edit" {...props}></Icon>
