<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmy9rcb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmy9rcb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cart-check-solid" {...props}></Icon>
