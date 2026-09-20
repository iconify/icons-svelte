<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/m/m1ogalbcw.css';
import '../../css/e/ebdvt6j7o.css';
import '../../css/b/bd9gczbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGYTFEIeOO"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="m1ogalbcw"/><path class="ebdvt6j7o"/></g></mask></defs><circle mask="url(#SVGYTFEIeOO)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:pen-circle-filled" {...props}></Icon>
