<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgtlrs60x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgtlrs60x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:badge-minus" {...props}></Icon>
