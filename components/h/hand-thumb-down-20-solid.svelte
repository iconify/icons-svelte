<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya6rrexwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ya6rrexwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-thumb-down-20-solid" {...props}></Icon>
