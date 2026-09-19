<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uk6juhlzl.css';
import '../../css/b/b6sl7kbuk.css';
import '../../css/i/ib__xqbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="uk6juhlzl"/><path class="b6sl7kbuk"/><path class="ib__xqbme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:box" {...props}></Icon>
