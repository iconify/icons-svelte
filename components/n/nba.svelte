<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy0k6tbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy0k6tbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nba" {...props}></Icon>
