<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oku0v98jv.css';
import '../../css/l/l93gu5f2n.css';
import '../../css/o/o23se-ntx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oku0v98jv"/><path class="l93gu5f2n"/><path class="o23se-ntx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lighthouse-20" {...props}></Icon>
