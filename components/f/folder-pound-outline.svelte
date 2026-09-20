<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn_mmh6jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn_mmh6jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-pound-outline" {...props}></Icon>
