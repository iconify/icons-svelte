<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghmu80r0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghmu80r0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jsfiddle" {...props}></Icon>
