<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6sel__is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":438,"height":512};
const content = `<path class="q6sel__is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dragula" {...props}></Icon>
