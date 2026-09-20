<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwtb6jfzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwtb6jfzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-right-line" {...props}></Icon>
