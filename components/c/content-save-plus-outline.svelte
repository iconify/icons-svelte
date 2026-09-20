<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-rehwbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-rehwbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-plus-outline" {...props}></Icon>
