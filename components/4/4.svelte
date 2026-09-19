<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqg11dbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":487,"height":775};
const content = `<path class="mqg11dbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:4" {...props}></Icon>
