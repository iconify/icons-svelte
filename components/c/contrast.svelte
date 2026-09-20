<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htqo9-sqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htqo9-sqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contrast" {...props}></Icon>
