<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g45yh2d2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g45yh2d2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-edit-outline" {...props}></Icon>
