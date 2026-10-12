<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndihgzbwa.css';
import '../../css/a/awn7h3b2c.css';
import '../../css/z/zkdyo_ief.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ndihgzbwa"/><path class="awn7h3b2c"/><path class="zkdyo_ief"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-minus-20" {...props}></Icon>
