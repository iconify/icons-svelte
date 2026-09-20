<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v58hasbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v58hasbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-p-circle" {...props}></Icon>
