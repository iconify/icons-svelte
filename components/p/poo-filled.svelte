<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zflz6tblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zflz6tblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:poo-filled" {...props}></Icon>
