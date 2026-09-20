<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hai481blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hai481blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-circle-fill" {...props}></Icon>
