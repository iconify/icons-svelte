<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ei0vgbcyu.css';
import '../../css/u/upm2ipmtj.css';
import '../../css/m/myfh07wzv.css';
import '../../css/o/of2dvxoml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ei0vgbcyu"/><path clip-rule="evenodd" class="upm2ipmtj"/><path class="myfh07wzv"/><path clip-rule="evenodd" class="of2dvxoml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bandage-outline" {...props}></Icon>
