<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwglqvu_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwglqvu_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:border-alt" {...props}></Icon>
