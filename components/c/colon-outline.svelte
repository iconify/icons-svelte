<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecu0gbbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ecu0gbbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:colon-outline" {...props}></Icon>
