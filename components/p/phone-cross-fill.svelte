<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxsznzm1o.css';
import '../../css/r/r20wh5g3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxsznzm1o"/><path class="r20wh5g3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-cross-fill" {...props}></Icon>
