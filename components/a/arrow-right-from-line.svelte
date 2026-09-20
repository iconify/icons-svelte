<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idq7gnb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idq7gnb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-right-from-line" {...props}></Icon>
