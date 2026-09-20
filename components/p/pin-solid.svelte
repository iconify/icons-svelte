<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx78nlbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx78nlbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-solid" {...props}></Icon>
