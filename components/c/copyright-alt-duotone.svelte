<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l4e6-gb8i.css';
import '../../css/a/ah3n7ppkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l4e6-gb8i"/><path class="ah3n7ppkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copyright-alt-duotone" {...props}></Icon>
