<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__wvsb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k__wvsb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:flu-mask-solid" {...props}></Icon>
