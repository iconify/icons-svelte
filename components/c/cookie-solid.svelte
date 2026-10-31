<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f61xg1bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f61xg1bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cookie-solid" {...props}></Icon>
