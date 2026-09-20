<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba35gmbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba35gmbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:42" {...props}></Icon>
