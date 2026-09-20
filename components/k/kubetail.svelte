<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqcszbc6x.css';
import '../../css/e/ety_7rmqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqcszbc6x"/><path class="ety_7rmqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubetail" {...props}></Icon>
