<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izgbh1b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="izgbh1b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-lizard" {...props}></Icon>
