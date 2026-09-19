<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b_ji3pbxg.css';
import '../../css/h/ho8edbc3c.css';
import '../../css/v/v9tvw21br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b_ji3pbxg"/><path class="ho8edbc3c"/><path class="v9tvw21br"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:object-select" {...props}></Icon>
