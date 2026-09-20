<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho2zi06nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho2zi06nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-sharp-duotone" {...props}></Icon>
