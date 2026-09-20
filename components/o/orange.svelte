<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me07f5bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me07f5bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:orange" {...props}></Icon>
