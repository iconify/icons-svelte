<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn1ngmb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn1ngmb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-desktop-slash-solid" {...props}></Icon>
