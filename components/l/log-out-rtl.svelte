<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbbc_v-5y.css';
import '../../css/v/vvfyzqbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mbbc_v-5y"/><path class="vvfyzqbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:log-out-rtl" {...props}></Icon>
