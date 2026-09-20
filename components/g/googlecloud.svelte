<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxubckb9w.css';
import '../../css/n/nbl00ebkt.css';
import '../../css/w/wtyrvmbzc.css';
import '../../css/h/hr-360lqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxubckb9w"/><path class="nbl00ebkt"/><path class="wtyrvmbzc"/><path class="hr-360lqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:googlecloud" {...props}></Icon>
