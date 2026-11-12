<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arfxhzlpu.css';
import '../../css/o/oxu08acul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="arfxhzlpu"/><path class="oxu08acul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minimus" {...props}></Icon>
