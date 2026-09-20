<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q7dhke2ou.css';
import '../../css/e/eqfcgpbth.css';
import '../../css/p/p4n2f7byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q7dhke2ou"/><path clip-rule="evenodd" class="eqfcgpbth"/><path clip-rule="evenodd" class="p4n2f7byf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:layers-light" {...props}></Icon>
