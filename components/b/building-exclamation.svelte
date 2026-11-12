<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dah875bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dah875bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-exclamation" {...props}></Icon>
