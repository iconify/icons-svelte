<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k9v3tvbiy.css';
import '../../css/o/owd--tbds.css';
import '../../css/h/hbedzngty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k9v3tvbiy"/><path class="owd--tbds"/><path class="hbedzngty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:plug-duotone" {...props}></Icon>
