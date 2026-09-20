<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivg8c9bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ivg8c9bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:earth" {...props}></Icon>
