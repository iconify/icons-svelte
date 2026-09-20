<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nww615dwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nww615dwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:lasso-tool-flat" {...props}></Icon>
