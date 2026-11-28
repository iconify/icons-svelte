<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei3fze0ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei3fze0ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-plus" {...props}></Icon>
