<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hca5gjt6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hca5gjt6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:robot-fill" {...props}></Icon>
