<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pn2ogq_7k.css';
import '../../css/n/nyagzdb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pn2ogq_7k"/><path class="nyagzdb8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:loading-2-fill" {...props}></Icon>
