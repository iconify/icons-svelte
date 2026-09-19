<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6en0pyme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="l6en0pyme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mars-double" {...props}></Icon>
