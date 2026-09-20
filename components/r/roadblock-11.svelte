<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b12a-lbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="b12a-lbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:roadblock-11" {...props}></Icon>
