<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-9as4bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-9as4bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:eject-square-solid" {...props}></Icon>
