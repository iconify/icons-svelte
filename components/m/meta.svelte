<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynlnm_cas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynlnm_cas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:meta" {...props}></Icon>
