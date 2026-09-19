<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch575kbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="ch575kbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hyves" {...props}></Icon>
