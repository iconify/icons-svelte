<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/owx3kbb2g.css';
import '../../css/v/v3nqf8b6y.css';
import '../../css/l/l7y-p8b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="owx3kbb2g"/><path class="v3nqf8b6y"/><path class="l7y-p8b_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:conference" {...props}></Icon>
