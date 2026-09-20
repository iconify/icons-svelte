<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j41oynb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j41oynb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bike" {...props}></Icon>
