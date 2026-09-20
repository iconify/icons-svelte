<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siglsi_5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siglsi_5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-simple-line" {...props}></Icon>
