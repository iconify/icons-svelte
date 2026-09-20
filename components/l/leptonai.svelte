<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evd8kfjws.css';
import '../../css/h/hxci04b3v.css';
import '../../css/w/wrzgswrqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="evd8kfjws"/><path clip-rule="evenodd" class="hxci04b3v"/><path class="wrzgswrqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:leptonai" {...props}></Icon>
