<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il83t9b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="il83t9b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-folder-open" {...props}></Icon>
