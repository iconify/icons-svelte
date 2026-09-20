<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alk9ttbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alk9ttbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beaker-check-outline" {...props}></Icon>
