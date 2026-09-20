<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmyfz1bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmyfz1bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubecraft-light" {...props}></Icon>
