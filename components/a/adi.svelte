<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu9gjds9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu9gjds9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:adi" {...props}></Icon>
