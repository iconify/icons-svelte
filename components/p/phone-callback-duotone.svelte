<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb7_855gm.css';
import '../../css/i/ipbkl_l6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb7_855gm"/><path class="ipbkl_l6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-callback-duotone" {...props}></Icon>
