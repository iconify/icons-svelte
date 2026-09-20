<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1kc6ccyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1kc6ccyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-alert-outline" {...props}></Icon>
