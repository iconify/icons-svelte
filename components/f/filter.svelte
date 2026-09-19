<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jerku_bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jerku_bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:filter" {...props}></Icon>
