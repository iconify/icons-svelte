<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaxx-ccaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaxx-ccaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:globe-check" {...props}></Icon>
