<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv7rk0b4n.css';
import '../../css/i/icd23tbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv7rk0b4n"/><path class="icd23tbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:at-circle-outline" {...props}></Icon>
