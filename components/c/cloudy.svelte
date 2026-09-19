<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qv8gs7hco.css';
import '../../css/t/to-usub9c.css';
import '../../css/d/dhl0amjcv.css';
import '../../css/b/b3akq5b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qv8gs7hco"/><path class="to-usub9c"/><path clip-rule="evenodd" class="dhl0amjcv"/><path class="b3akq5b3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:cloudy" {...props}></Icon>
