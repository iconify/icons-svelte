<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8jp68q7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b8jp68q7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anguished-face-in-circle" {...props}></Icon>
