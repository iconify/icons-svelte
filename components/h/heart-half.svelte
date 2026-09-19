<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bapm2gryp.css';
import '../../css/k/kwvzbylod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bapm2gryp"/><path class="kwvzbylod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:heart-half" {...props}></Icon>
