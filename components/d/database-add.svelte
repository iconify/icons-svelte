<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uxbpr3bwv.css';
import '../../css/t/tdkn-_t-r.css';
import '../../css/m/mwz9-fkga.css';
import '../../css/m/md402plbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uxbpr3bwv"/><path class="tdkn-_t-r"/><ellipse class="mwz9-fkga"/><path class="md402plbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database-add" {...props}></Icon>
