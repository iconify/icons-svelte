<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdxc7ob4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdxc7ob4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:fitbit-logo" {...props}></Icon>
