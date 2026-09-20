<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah3pnpibj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ah3pnpibj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:download-square-solid" {...props}></Icon>
