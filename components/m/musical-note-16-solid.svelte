<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh3vw6hqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fh3vw6hqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:musical-note-16-solid" {...props}></Icon>
