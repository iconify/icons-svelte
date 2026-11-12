<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwvjmvb6c.css';
import '../../css/o/ogd77sb1i.css';
import '../../css/g/g4-80-g_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwvjmvb6c"/><path class="ogd77sb1i"/><path class="g4-80-g_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beaver-habit-tracker" {...props}></Icon>
