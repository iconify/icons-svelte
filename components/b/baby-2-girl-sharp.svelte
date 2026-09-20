<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/morvqxt_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="morvqxt_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:baby-2-girl-sharp" {...props}></Icon>
