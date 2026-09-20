<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwmlxiynb.css';
import '../../css/j/jdfmcfbkc.css';
import '../../css/y/yy8aoacbq.css';
import '../../css/e/efnborbkf.css';
import '../../css/f/feuxlfrmn.css';
import '../../css/d/deicl5brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwmlxiynb"/><path clip-rule="evenodd" class="jdfmcfbkc"/><path class="yy8aoacbq"/><path class="efnborbkf"/><path class="feuxlfrmn"/><path clip-rule="evenodd" class="deicl5brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fida" {...props}></Icon>
