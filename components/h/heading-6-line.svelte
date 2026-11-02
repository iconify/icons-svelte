<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba-9j369s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-9j369s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-6-line" {...props}></Icon>
