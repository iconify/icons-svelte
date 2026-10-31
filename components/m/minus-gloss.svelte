<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iubtq7foy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iubtq7foy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minus-gloss" {...props}></Icon>
