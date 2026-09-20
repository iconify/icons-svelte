<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqfaxx8mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tqfaxx8mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-mental-health" {...props}></Icon>
