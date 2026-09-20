<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axq885ryf.css';
import '../../css/f/fegcs2boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="axq885ryf"/><path clip-rule="evenodd" class="fegcs2boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:360-solid" {...props}></Icon>
