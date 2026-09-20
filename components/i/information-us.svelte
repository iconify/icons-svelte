<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcjq7gb3l.css';
import '../../css/h/hgh3anbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="vcjq7gb3l"/><path class="hgh3anbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:information-us" {...props}></Icon>
