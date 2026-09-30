<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj0d70bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj0d70bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:octagon" {...props}></Icon>
