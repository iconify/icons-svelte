<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fno-s8bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fno-s8bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:host-maintenance" {...props}></Icon>
