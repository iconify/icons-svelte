<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctbrky6mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctbrky6mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:battery-medium-3-solid" {...props}></Icon>
