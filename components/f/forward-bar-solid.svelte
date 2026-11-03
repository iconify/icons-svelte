<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl7yb5rrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl7yb5rrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:forward-bar-solid" {...props}></Icon>
