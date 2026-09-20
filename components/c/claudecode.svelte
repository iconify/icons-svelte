<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au73r9tay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="au73r9tay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:claudecode" {...props}></Icon>
