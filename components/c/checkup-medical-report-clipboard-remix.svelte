<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emw2e35wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="emw2e35wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:checkup-medical-report-clipboard-remix" {...props}></Icon>
