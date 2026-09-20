<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw0b-1bmv.css';
import '../../css/w/wh-70pu7h.css';
import '../../css/d/d788uf64t.css';
import '../../css/o/oe3oz-bur.css';
import '../../css/a/amcescb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hw0b-1bmv"/><path class="wh-70pu7h"/><path class="d788uf64t"/><path class="oe3oz-bur"/><path class="amcescb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-sound" {...props}></Icon>
