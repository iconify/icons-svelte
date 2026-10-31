<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bccip5bwi.css';
import '../../css/f/fadplwb6f.css';
import '../../css/m/mhu84h7pt.css';
import '../../css/e/epbh144fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bccip5bwi wm-shadow"/><path class="fadplwb6f wm-shadow"/><path class="mhu84h7pt"/><path class="epbh144fv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:contrast" {...props}></Icon>
