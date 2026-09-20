<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tf6i70b4y.css';
import '../../css/n/noyct1bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tf6i70b4y"/><path class="noyct1bbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bus-duotone" {...props}></Icon>
