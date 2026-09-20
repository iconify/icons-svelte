<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svl07cy6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svl07cy6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-right-left-solid" {...props}></Icon>
