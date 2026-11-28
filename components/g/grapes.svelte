<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfk181vqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfk181vqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:grapes" {...props}></Icon>
