<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svskq2bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svskq2bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:lasso-tool-solid" {...props}></Icon>
