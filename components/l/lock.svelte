<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/z/z9qk59bdu.css';
import '../../css/o/o41m9g48r.css';
import '../../css/h/hmcoah3hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="z9qk59bdu"/><path class="o41m9g48r"/><path class="hmcoah3hh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:lock" {...props}></Icon>
