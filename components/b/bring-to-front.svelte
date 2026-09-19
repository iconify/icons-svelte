<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pea7082vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pea7082vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bring-to-front" {...props}></Icon>
