<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzx8i8ica.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bzx8i8ica"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck" {...props}></Icon>
