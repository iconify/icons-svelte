<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsfc7lqru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="nsfc7lqru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:plus" {...props}></Icon>
