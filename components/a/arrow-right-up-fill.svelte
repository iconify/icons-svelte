<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq70-9bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq70-9bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-up-fill" {...props}></Icon>
