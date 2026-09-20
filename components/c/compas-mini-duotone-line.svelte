<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o58hkebvg.css';
import '../../css/x/xjghu547v.css';
import '../../css/b/btizuutzp.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGfvUskeMK"><g class="o58hkebvg"><path class="xjghu547v"/><circle class="btizuutzp"/></g></mask></defs><path mask="url(#SVGfvUskeMK)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:compas-mini-duotone-line" {...props}></Icon>
