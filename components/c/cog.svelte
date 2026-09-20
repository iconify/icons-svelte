<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/remi148dy.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/h/hwsal5q-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="remi148dy"/><circle class="h_tsn8bxt"/><circle class="hwsal5q-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cog" {...props}></Icon>
