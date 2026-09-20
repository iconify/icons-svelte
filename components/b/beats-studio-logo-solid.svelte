<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk8is5but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zk8is5but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:beats-studio-logo-solid" {...props}></Icon>
