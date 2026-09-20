<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl8fc0bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="cl8fc0bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:check-xs" {...props}></Icon>
