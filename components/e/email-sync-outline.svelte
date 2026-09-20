<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdg08x6jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdg08x6jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-sync-outline" {...props}></Icon>
