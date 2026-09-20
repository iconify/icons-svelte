<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-bbp7lwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bbp7lwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:health-circle-fill" {...props}></Icon>
