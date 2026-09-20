<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnnmw2ayq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qnnmw2ayq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:restaurant" {...props}></Icon>
