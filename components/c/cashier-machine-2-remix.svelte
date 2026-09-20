<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz5y4by4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz5y4by4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cashier-machine-2-remix" {...props}></Icon>
