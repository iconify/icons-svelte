<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i25dcsbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i25dcsbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:information-o" {...props}></Icon>
