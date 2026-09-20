<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dda_q--5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dda_q--5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-sharp" {...props}></Icon>
