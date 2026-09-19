<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/h/hf2-qhbfh.css';
import '../../css/i/iu_7h2b0u.css';
import '../../css/v/vytau2beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="hf2-qhbfh"/><path class="iu_7h2b0u"/><path class="vytau2beg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:align-text-right-one" {...props}></Icon>
