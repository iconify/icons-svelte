<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miej-3nwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miej-3nwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-right-square-fill" {...props}></Icon>
