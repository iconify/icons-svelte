<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0dfacccx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0dfacccx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:megaphone-2-solid" {...props}></Icon>
