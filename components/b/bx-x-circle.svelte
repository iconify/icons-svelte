<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxj-53b3o.css';
import '../../css/v/vdkkambso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxj-53b3o"/><path class="vdkkambso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-x-circle" {...props}></Icon>
