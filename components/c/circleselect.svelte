<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-g2blbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-g2blbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleselect" {...props}></Icon>
