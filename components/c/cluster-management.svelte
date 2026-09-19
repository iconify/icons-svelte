<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkacrgbkn.css';
import '../../css/f/fhr0udsbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkacrgbkn"/><path class="fhr0udsbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cluster-management" {...props}></Icon>
