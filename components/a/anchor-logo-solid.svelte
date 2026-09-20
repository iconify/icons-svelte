<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iedmqkb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iedmqkb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:anchor-logo-solid" {...props}></Icon>
