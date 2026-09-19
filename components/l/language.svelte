<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey_qkc5et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey_qkc5et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:language" {...props}></Icon>
