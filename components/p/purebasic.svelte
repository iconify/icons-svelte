<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svv1otbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="svv1otbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:purebasic" {...props}></Icon>
