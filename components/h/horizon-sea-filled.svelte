<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy97d27iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy97d27iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizon-sea-filled" {...props}></Icon>
