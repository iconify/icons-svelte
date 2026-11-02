<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_78s8hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1_78s8hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-add-fill" {...props}></Icon>
