<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at92ugbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="at92ugbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:datagrip" {...props}></Icon>
