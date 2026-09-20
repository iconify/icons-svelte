<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcykceb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcykceb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:health-care-2-flat" {...props}></Icon>
