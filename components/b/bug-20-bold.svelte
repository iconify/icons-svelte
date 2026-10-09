<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcy6jh_of.css';
import '../../css/r/rx-p80tpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lcy6jh_of"/><path class="rx-p80tpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bug-20-bold" {...props}></Icon>
