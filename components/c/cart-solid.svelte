<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nzsjbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2nzsjbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cart-solid" {...props}></Icon>
