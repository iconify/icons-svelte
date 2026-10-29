<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/phys5gjml.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/f/fz9wbhbib.css';
import '../../css/m/mktqs86uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="phys5gjml wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="fz9wbhbib wm-k"/><path class="mktqs86uc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-left-open-blueprint" {...props}></Icon>
