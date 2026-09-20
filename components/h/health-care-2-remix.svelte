<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlnkqsi2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xlnkqsi2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:health-care-2-remix" {...props}></Icon>
