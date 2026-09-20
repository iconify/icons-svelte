<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knti61bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knti61bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-up-right-2-fill" {...props}></Icon>
