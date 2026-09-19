<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyj4tfarm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1046.16,"height":1000};
const content = `<path class="oyj4tfarm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:linkedin" {...props}></Icon>
