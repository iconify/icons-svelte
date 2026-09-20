<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw10dub5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw10dub5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heart-sharp-fill" {...props}></Icon>
