<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bq6pbys6j.css';
import '../../css/g/gizcmhyva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bq6pbys6j"/><path class="gizcmhyva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:castle-duotone" {...props}></Icon>
