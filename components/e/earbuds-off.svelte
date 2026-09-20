<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ust0jibvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ust0jibvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:earbuds-off" {...props}></Icon>
