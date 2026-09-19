<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b22ju_bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="b22ju_bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:delicious" {...props}></Icon>
