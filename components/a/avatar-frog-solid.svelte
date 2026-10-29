<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elro_nbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elro_nbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-frog-solid" {...props}></Icon>
