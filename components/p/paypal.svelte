<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5rg4yowh.css';
import '../../css/n/nexfdi4-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5rg4yowh"/><path class="nexfdi4-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:paypal" {...props}></Icon>
