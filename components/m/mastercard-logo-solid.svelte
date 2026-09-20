<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppdbs_bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppdbs_bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mastercard-logo-solid" {...props}></Icon>
