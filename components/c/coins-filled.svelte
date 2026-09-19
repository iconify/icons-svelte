<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxbs97bbo.css';
import '../../css/v/v_sj4-bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxbs97bbo"/><circle class="v_sj4-bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:coins-filled" {...props}></Icon>
