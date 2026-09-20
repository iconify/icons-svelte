<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgk0sjdeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgk0sjdeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-frown-sharp" {...props}></Icon>
