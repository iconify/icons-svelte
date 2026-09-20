<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iztd4sbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iztd4sbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:logout-1-remix" {...props}></Icon>
