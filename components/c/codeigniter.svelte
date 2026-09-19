<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtx-7sn0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dtx-7sn0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:codeigniter" {...props}></Icon>
