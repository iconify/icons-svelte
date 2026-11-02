<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_9q6qt6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_9q6qt6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-9-fill" {...props}></Icon>
