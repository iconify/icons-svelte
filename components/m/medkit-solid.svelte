<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd610k6nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd610k6nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:medkit-solid" {...props}></Icon>
