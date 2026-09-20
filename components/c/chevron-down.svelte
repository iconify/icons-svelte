<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk-yam33n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk-yam33n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-down" {...props}></Icon>
