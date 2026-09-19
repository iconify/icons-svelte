<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/ekwamnsnd.css';
import '../../css/n/nht6_fbko.css';
import '../../css/l/lmu8d6bcl.css';
import '../../css/u/uztmj3dza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="ekwamnsnd"/><ellipse class="nht6_fbko"/><ellipse class="lmu8d6bcl"/><path class="uztmj3dza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:medium-square" {...props}></Icon>
