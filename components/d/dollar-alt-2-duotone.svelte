<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v-p5pib2x.css';
import '../../css/h/hak26odoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v-p5pib2x"/><path class="hak26odoa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-alt-2-duotone" {...props}></Icon>
