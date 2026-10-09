<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjbwlsbfm.css';
import '../../css/m/mdtq3-bqo.css';
import '../../css/l/l7fvvsb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jjbwlsbfm"/><path class="mdtq3-bqo"/><path class="l7fvvsb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:megaphone-20-bold" {...props}></Icon>
