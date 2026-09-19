<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lie2npblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="lie2npblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:playstation" {...props}></Icon>
