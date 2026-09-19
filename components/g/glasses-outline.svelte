<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm8ug-bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm8ug-bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:glasses-outline" {...props}></Icon>
