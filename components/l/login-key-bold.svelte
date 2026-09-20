<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xta6e_j8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xta6e_j8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:login-key-bold" {...props}></Icon>
