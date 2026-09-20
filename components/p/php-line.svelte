<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou2w_pd9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou2w_pd9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:php-line" {...props}></Icon>
