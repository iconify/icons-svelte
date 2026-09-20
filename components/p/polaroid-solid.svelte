<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpt2ttbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpt2ttbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:polaroid-solid" {...props}></Icon>
