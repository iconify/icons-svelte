<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luk64wbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="luk64wbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:orthogon9x7" {...props}></Icon>
