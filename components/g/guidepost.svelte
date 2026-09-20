<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eon-qub9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eon-qub9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:guidepost" {...props}></Icon>
