<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1u1o_u1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="w1u1o_u1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:brush" {...props}></Icon>
