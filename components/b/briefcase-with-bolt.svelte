<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj7d2mlel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hj7d2mlel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-bolt" {...props}></Icon>
