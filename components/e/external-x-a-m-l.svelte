<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-zswn07o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n-zswn07o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:external-x-a-m-l" {...props}></Icon>
