<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6mz-dumd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="f6mz-dumd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:cookpad" {...props}></Icon>
