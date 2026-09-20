<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yne9jju8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yne9jju8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:massachusetts" {...props}></Icon>
