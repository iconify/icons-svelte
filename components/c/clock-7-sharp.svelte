<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgqmgcdgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgqmgcdgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-7-sharp" {...props}></Icon>
