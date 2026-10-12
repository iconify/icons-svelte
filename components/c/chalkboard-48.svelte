<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uku-79btt.css';
import '../../css/f/fbdvput5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uku-79btt"/><path class="fbdvput5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chalkboard-48" {...props}></Icon>
