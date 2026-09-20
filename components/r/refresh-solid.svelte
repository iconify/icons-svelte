<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkd2uny5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wkd2uny5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:refresh-solid" {...props}></Icon>
