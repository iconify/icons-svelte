<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/v/v90gbqbox.css';
import '../../css/h/hig_ndo4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="h_tsn8bxt"/><circle class="v90gbqbox"/><path class="hig_ndo4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:onion" {...props}></Icon>
