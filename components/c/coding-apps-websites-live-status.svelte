<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx5rh7b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sx5rh7b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-live-status" {...props}></Icon>
