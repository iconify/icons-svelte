<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddqrdktkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddqrdktkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:map-pin-plus-sharp" {...props}></Icon>
