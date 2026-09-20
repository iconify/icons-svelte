<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovhjtnbtq.css';
import '../../css/v/vm3bmsb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovhjtnbtq"/><path class="vm3bmsb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:american-express-logo-solid" {...props}></Icon>
