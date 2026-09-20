<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqz_0b6fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqz_0b6fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-fill" {...props}></Icon>
