<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esi0okb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esi0okb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:image-02" {...props}></Icon>
