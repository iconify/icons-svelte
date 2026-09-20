<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibtzbzotr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibtzbzotr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-import-outline" {...props}></Icon>
