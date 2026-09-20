<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l4e6-gb8i.css';
import '../../css/y/y6h6rjbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l4e6-gb8i"/><path class="y6h6rjbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:nope-duotone" {...props}></Icon>
