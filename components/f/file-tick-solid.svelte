<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3tb05bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z3tb05bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-tick-solid" {...props}></Icon>
