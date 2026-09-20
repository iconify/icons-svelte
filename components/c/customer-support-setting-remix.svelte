<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jegat8g5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jegat8g5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:customer-support-setting-remix" {...props}></Icon>
