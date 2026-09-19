<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/a/aoaqowbnh.css';
import '../../css/f/fmzg4fbof.css';
import '../../css/e/eep_kvb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="aoaqowbnh"/><path class="fmzg4fbof"/><path class="eep_kvb3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:beer" {...props}></Icon>
