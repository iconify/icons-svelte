<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec5wflrnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec5wflrnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation-2-solid" {...props}></Icon>
