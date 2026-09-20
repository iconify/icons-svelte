<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_p73mbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_p73mbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:facebook-messenger-alt" {...props}></Icon>
