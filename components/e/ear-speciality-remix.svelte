<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wszer9whm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wszer9whm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ear-speciality-remix" {...props}></Icon>
