<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/flz5ptbrm.css';
import '../../css/n/n4mhsebtw.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/l9l1aybwd.css';
import '../../css/q/q8q-_p06m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="flz5ptbrm"/><mask id="SVGcFaS5cXn" width="32" height="24" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path clip-rule="evenodd" class="n4mhsebtw"/></mask><g clip-rule="evenodd" mask="url(#SVGcFaS5cXn)" class="d2kvgvbvc"><path class="l9l1aybwd"/><path class="q8q-_p06m"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:lt" {...props}></Icon>
