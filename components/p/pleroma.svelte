<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is_bib.css';
import '../../css/y/ydovum.css';
import '../../css/r/rek8ly.css';
import '../../css/d/d_veic.css';
import '../../css/d/d-g-t0ye.css';
import '../../css/d/d-u2wfvb.css';
import '../../css/d/d-tpcgta.css';
import '../../css/d/d-y53qgi.css';
import '../../css/d/d-ysi9rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is_bib ydovum"/><path class="rek8ly ydovum"/><path class="d_veic ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:pleroma" {...props}></Icon>
