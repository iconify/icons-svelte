<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9wuyqb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9wuyqb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-vertical" {...props}></Icon>
