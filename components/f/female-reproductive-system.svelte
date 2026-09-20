<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr-jp9bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hr-jp9bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:female-reproductive-system" {...props}></Icon>
