<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr5qjmbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":529,"height":1000};
const content = `<path class="cr5qjmbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:down-dir" {...props}></Icon>
