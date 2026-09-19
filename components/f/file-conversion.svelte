<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km1zm6hiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="km1zm6hiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-conversion" {...props}></Icon>
