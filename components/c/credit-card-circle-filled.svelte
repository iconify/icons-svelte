<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/w/w_340yi4i.css';
import '../../css/n/n2f03twwq.css';
import '../../css/b/bd9gczbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGDVsLnPCD"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="w_340yi4i"/><path class="n2f03twwq"/></g></mask></defs><circle mask="url(#SVGDVsLnPCD)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:credit-card-circle-filled" {...props}></Icon>
