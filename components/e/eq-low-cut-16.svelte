<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6jyqhex.css';
import '../../css/f/f6s9xdlma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gs6jyqhex"/><path class="f6s9xdlma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eq-low-cut-16" {...props}></Icon>
