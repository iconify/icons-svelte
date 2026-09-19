<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv_z3ob6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv_z3ob6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:block-quote" {...props}></Icon>
