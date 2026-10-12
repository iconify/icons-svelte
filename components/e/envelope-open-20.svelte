<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnati2tjw.css';
import '../../css/j/junk1jcyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rnati2tjw"/><path class="junk1jcyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:envelope-open-20" {...props}></Icon>
