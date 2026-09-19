<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv41wkk5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="gv41wkk5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bank" {...props}></Icon>
