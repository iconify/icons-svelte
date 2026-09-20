<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p9gycnbjq.css';
import '../../css/i/iqhj61bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p9gycnbjq"/><path class="iqhj61bhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-duotone" {...props}></Icon>
