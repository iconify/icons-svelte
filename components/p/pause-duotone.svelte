<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7p8u_bgx.css';
import '../../css/t/t2z2jnber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7p8u_bgx"/><path class="t2z2jnber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pause-duotone" {...props}></Icon>
