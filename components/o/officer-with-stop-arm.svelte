<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-jfigb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o-jfigb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:officer-with-stop-arm" {...props}></Icon>
