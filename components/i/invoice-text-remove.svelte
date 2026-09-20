<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z115q0a9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z115q0a9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-remove" {...props}></Icon>
