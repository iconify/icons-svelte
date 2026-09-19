<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3j61h5fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="b3j61h5fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:indent-more" {...props}></Icon>
