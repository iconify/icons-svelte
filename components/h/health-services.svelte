<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-a9q7i-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="n-a9q7i-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:health-services" {...props}></Icon>
