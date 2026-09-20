<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgl81vc3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgl81vc3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-times" {...props}></Icon>
