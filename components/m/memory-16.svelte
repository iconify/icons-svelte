<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx94_1hhr.css';
import '../../css/t/tde2ctmpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tx94_1hhr"/><path clip-rule="evenodd" class="tde2ctmpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:memory-16" {...props}></Icon>
