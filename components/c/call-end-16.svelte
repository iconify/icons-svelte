<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfmfw0brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lfmfw0brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-end-16" {...props}></Icon>
