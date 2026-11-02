<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyu5i9bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyu5i9bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bill-line" {...props}></Icon>
