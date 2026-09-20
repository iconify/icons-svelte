<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk6bg3bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk6bg3bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heart" {...props}></Icon>
