<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne1xvo82d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ne1xvo82d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infrared-panel-20" {...props}></Icon>
