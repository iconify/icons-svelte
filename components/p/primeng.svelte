<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obusc8bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obusc8bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:primeng" {...props}></Icon>
