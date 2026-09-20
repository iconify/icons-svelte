<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7m2gubse.css';
import '../../css/o/ocdt_ibwk.css';
import '../../css/h/hz83yxben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7m2gubse"/><path class="ocdt_ibwk"/><path class="hz83yxben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:jungle4eos" {...props}></Icon>
