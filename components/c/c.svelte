<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpma81dsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpma81dsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:c" {...props}></Icon>
