<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj0w1_9qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj0w1_9qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:moneybag-alt" {...props}></Icon>
