<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa1rnmbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oa1rnmbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insurance-48" {...props}></Icon>
