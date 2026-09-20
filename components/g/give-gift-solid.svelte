<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcw8lebxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcw8lebxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:give-gift-solid" {...props}></Icon>
