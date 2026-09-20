<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ethn8sb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ethn8sb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:controller-wireless-solid" {...props}></Icon>
