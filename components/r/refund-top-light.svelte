<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ugmmbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3ugmmbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refund-top-light" {...props}></Icon>
