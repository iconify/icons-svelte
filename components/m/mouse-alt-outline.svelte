<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iimgyyl1w.css';
import '../../css/d/dta0--2ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iimgyyl1w"/><path clip-rule="evenodd" class="dta0--2ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:mouse-alt-outline" {...props}></Icon>
