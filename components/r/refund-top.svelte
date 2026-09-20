<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6g7qtnxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6g7qtnxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refund-top" {...props}></Icon>
