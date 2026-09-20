<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bogds5biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bogds5biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pixabay" {...props}></Icon>
