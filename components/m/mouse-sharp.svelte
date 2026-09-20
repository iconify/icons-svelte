<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra01bjbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra01bjbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mouse-sharp" {...props}></Icon>
