<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja8d0ui8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ja8d0ui8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-frown" {...props}></Icon>
