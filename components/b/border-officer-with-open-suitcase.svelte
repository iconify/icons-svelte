<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgfs6lbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qgfs6lbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:border-officer-with-open-suitcase" {...props}></Icon>
