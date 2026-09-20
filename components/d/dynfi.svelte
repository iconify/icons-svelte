<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biipsdsmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="biipsdsmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynfi" {...props}></Icon>
