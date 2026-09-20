<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inf7f8bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inf7f8bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-plus-sharp" {...props}></Icon>
