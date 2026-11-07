<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/l/lbue7y00m.css';
import '../../css/t/twoigx9_z.css';
import '../../css/r/rg7rardxv.css';
import '../../css/b/b6-nrrb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="lbue7y00m"/><path class="twoigx9_z"/><path class="rg7rardxv"/></g><path class="b6-nrrb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-minus-minimalistic-bold-duotone" {...props}></Icon>
