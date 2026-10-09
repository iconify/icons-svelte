<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjnxpnb1o.css';
import '../../css/m/mr3oerbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xjnxpnb1o"/><path class="mr3oerbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-substation-20" {...props}></Icon>
