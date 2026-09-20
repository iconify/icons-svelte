<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgb68_bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lgb68_bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-laptop" {...props}></Icon>
