<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3k491x4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3k491x4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chair-2-solid" {...props}></Icon>
