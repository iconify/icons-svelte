<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi704w7_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi704w7_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:image" {...props}></Icon>
