<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnm4t1t0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gnm4t1t0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:mobile-phone-solid" {...props}></Icon>
