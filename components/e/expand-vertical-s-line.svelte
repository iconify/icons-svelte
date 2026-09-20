<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6se2ob5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6se2ob5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-vertical-s-line" {...props}></Icon>
