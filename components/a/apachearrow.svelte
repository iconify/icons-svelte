<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je-x1rbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je-x1rbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachearrow" {...props}></Icon>
