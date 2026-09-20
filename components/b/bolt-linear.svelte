<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd1l1p81t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd1l1p81t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bolt-linear" {...props}></Icon>
