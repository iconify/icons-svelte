<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di16lc9hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="di16lc9hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:infuse-two-filled" {...props}></Icon>
