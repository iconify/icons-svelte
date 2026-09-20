<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdatwkffh.css';
import '../../css/u/ux686dk8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bdatwkffh"/><path class="ux686dk8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-pharmacy" {...props}></Icon>
