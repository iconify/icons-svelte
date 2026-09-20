<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrdaxubdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrdaxubdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:key-remove" {...props}></Icon>
