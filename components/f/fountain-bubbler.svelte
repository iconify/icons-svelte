<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it_1ksbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="it_1ksbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fountain-bubbler" {...props}></Icon>
