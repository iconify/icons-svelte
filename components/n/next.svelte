<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdvy41q8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdvy41q8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:next" {...props}></Icon>
