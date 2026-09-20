<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lejv3lbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lejv3lbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-eye" {...props}></Icon>
