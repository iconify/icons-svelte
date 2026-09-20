<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izbeoyb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izbeoyb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-angry-outline" {...props}></Icon>
