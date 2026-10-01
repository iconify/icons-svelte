<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-dnt8gvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-dnt8gvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:claude-code" {...props}></Icon>
