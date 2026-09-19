<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz6astb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="hz6astb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hourglass-start" {...props}></Icon>
