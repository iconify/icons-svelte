<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n07h6uase.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n07h6uase"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-remove-outline" {...props}></Icon>
