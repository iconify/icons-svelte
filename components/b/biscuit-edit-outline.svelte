<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czvithbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czvithbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-edit-outline" {...props}></Icon>
