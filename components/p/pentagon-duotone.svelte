<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jf20jabau.css';
import '../../css/m/m9wpyibap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jf20jabau"/><path class="m9wpyibap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pentagon-duotone" {...props}></Icon>
