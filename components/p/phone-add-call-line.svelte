<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppmm91byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppmm91byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-add-call-line" {...props}></Icon>
