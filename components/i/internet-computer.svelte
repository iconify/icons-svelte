<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr3g4nxfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr3g4nxfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:internet-computer" {...props}></Icon>
