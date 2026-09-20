<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukvxzvmz.css';
import '../../css/f/fyt8axbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vukvxzvmz"/><path class="fyt8axbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:pediatrics" {...props}></Icon>
