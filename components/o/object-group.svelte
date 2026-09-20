<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a334iw3hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a334iw3hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:object-group" {...props}></Icon>
