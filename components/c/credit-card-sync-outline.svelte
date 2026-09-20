<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbb0gcc7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbb0gcc7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-sync-outline" {...props}></Icon>
