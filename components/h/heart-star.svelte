<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h908iiygx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h908iiygx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-star" {...props}></Icon>
