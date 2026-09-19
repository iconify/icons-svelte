<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjwn39bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":512};
const content = `<path class="jjwn39bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:miranda" {...props}></Icon>
