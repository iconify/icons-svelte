<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djun2xb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djun2xb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:celsius" {...props}></Icon>
