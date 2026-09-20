<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp5m3lbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wp5m3lbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:heart-rate-clipboard-remix" {...props}></Icon>
