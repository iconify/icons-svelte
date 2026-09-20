<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdc5ildnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdc5ildnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:heart-medical" {...props}></Icon>
