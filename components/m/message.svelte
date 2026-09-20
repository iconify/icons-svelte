<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5_-1qffs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5_-1qffs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message" {...props}></Icon>
