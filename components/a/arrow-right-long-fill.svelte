<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wydghv23s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wydghv23s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-long-fill" {...props}></Icon>
