<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovnp5lb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovnp5lb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:plus-ten-circle" {...props}></Icon>
