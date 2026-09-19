<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fjbqe5tiw.css';
import '../../css/r/rk-rw9bqk.css';
import '../../css/a/a7-m_liew.css';
import '../../css/k/k1d0jkbam.css';
import '../../css/u/uiyiq56du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="fjbqe5tiw"/><circle class="rk-rw9bqk"/><path class="a7-m_liew"/><circle class="k1d0jkbam"/><path class="uiyiq56du"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-one" {...props}></Icon>
