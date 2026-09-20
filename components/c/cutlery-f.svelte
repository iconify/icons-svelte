<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx1---vpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<path class="fx1---vpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cutlery-f" {...props}></Icon>
