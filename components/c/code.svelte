<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/som5nvb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="som5nvb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:code" {...props}></Icon>
