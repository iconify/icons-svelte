<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o58hkebvg.css';
import '../../css/n/npb8tdb2y.css';
import '../../css/y/ye_02ub4x.css';
import '../../css/l/lz8k0cc0q.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGgDUkKebO"><g class="o58hkebvg"><path class="npb8tdb2y"/><path class="ye_02ub4x"/><path class="lz8k0cc0q"/></g></mask></defs><path mask="url(#SVGgDUkKebO)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:direction-duotone-line" {...props}></Icon>
