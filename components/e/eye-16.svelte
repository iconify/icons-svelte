<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3erhq7-p.css';
import '../../css/m/m5_1mibrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y3erhq7-p"/><path clip-rule="evenodd" class="m5_1mibrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eye-16" {...props}></Icon>
