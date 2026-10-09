<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewn1ke3br.css';
import '../../css/z/zgnbte-qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="zgnbte-qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:columns-20" {...props}></Icon>
