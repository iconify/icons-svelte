<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-ehlsbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ehlsbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-bold-box-outline" {...props}></Icon>
