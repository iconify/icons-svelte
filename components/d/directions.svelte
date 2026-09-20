<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6oy1q_yr.css';
import '../../css/c/c14mgt73k.css';
import '../../css/x/xq8wemwrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6oy1q_yr"/><path class="c14mgt73k"/><path class="xq8wemwrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:directions" {...props}></Icon>
