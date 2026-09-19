<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g775v9b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="g775v9b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:dot-circle-o" {...props}></Icon>
