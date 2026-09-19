<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjp3leb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="jjp3leb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-alt" {...props}></Icon>
