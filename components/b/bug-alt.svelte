<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3utn-y9c.css';
import '../../css/j/jjp5tkp_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3utn-y9c"/><path class="jjp5tkp_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bug-alt" {...props}></Icon>
