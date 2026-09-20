<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnegrza5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnegrza5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:baby-boy-sharp-two-tone" {...props}></Icon>
