<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byrk5zf9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byrk5zf9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dislike-solid" {...props}></Icon>
