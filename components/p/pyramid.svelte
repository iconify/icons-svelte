<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed8jw0b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ed8jw0b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pyramid" {...props}></Icon>
