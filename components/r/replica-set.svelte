<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhrg354jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhrg354jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:replica-set" {...props}></Icon>
