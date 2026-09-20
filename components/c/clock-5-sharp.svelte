<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9x7dzbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9x7dzbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-5-sharp" {...props}></Icon>
