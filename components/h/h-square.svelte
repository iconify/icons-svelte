<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzzkz4bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bzzkz4bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:h-square" {...props}></Icon>
