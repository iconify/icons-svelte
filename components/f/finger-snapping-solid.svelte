<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz727r4ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tz727r4ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:finger-snapping-solid" {...props}></Icon>
