<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9iekghug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f9iekghug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bars-3-bottom-center-solid" {...props}></Icon>
