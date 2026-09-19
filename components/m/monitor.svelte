<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znqcmcbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znqcmcbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:monitor" {...props}></Icon>
