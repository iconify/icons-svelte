<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhso8hlxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhso8hlxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chicken-leg-filled" {...props}></Icon>
