<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rop--mbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rop--mbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:channel" {...props}></Icon>
