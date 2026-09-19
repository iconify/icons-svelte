<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9q94dj6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":11};
const content = `<path class="s9q94dj6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:open" {...props}></Icon>
