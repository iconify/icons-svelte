<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz4v40_rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hz4v40_rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bag-pound-remix" {...props}></Icon>
