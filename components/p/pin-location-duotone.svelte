<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2dud7gav.css';
import '../../css/k/kfcxw6ofm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2dud7gav"/><path class="kfcxw6ofm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pin-location-duotone" {...props}></Icon>
