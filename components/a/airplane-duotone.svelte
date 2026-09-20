<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o4cq3vwgd.css';
import '../../css/j/jubmfqrov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o4cq3vwgd"/><path class="jubmfqrov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:airplane-duotone" {...props}></Icon>
