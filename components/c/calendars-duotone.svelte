<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g2mi622fc.css';
import '../../css/r/rwbaszb0j.css';
import '../../css/c/c-4w8acaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g2mi622fc"/><path class="rwbaszb0j"/><path class="c-4w8acaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendars-duotone" {...props}></Icon>
