<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylhdevp5c.css';
import '../../css/v/v-gec3bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ylhdevp5c"/><path class="v-gec3bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:focus-center-16" {...props}></Icon>
