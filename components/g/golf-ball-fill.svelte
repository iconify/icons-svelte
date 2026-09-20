<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpodlbzms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpodlbzms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:golf-ball-fill" {...props}></Icon>
