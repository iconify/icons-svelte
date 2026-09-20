<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rls_dv.css';
import '../../css/s/so-from-70.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rls_dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chat-bubble" {...props}></Icon>
