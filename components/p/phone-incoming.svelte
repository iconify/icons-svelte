<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvbubjb1v.css';
import '../../css/m/mh-rg_bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbubjb1v"/><path class="mh-rg_bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:phone-incoming" {...props}></Icon>
