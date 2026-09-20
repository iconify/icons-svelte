<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgak7bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgak7bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ko-fi" {...props}></Icon>
