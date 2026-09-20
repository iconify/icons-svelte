<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jov7b6hyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jov7b6hyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:comment" {...props}></Icon>
