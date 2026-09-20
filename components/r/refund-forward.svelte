<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8yw1dbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8yw1dbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refund-forward" {...props}></Icon>
