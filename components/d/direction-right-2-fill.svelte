<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgb9rmbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgb9rmbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-right-2-fill" {...props}></Icon>
