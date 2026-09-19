<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2uer03cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x2uer03cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:instagram" {...props}></Icon>
