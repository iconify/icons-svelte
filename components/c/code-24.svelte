<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd1sf9boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd1sf9boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-24" {...props}></Icon>
