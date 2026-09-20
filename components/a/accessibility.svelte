<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytib-nb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytib-nb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:accessibility" {...props}></Icon>
