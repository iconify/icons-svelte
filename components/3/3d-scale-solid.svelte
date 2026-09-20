<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk4wjunik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pk4wjunik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:3d-scale-solid" {...props}></Icon>
