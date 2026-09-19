<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocb0_hbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="ocb0_hbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:outdent" {...props}></Icon>
