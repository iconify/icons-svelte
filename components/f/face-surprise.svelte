<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brbyr1_7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brbyr1_7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-surprise" {...props}></Icon>
