<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk2co3bdu.css';
import '../../css/p/ph74n2b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fk2co3bdu"/><path class="ph74n2b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-linen-48" {...props}></Icon>
