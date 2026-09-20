<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tne5lpbaz.css';
import '../../css/t/tylyzabts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tne5lpbaz"/><path class="tylyzabts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:note-solid" {...props}></Icon>
