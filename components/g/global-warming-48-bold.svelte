<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx-xmmb2t.css';
import '../../css/o/ohm3jmbqg.css';
import '../../css/m/mzottzalv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nx-xmmb2t"/><path class="ohm3jmbqg"/><path class="mzottzalv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:global-warming-48-bold" {...props}></Icon>
