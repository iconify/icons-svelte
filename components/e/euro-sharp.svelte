<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llh2edb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llh2edb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:euro-sharp" {...props}></Icon>
