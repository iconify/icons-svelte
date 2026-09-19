<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yldf2lb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":614};
const content = `<path class="yldf2lb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:down" {...props}></Icon>
