<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zju57bchu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zju57bchu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bell-set-timer-solid" {...props}></Icon>
