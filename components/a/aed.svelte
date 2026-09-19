<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq4e_bcin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq4e_bcin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:aed" {...props}></Icon>
