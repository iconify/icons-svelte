<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq3t-owyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zq3t-owyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:border-bottom-solid" {...props}></Icon>
