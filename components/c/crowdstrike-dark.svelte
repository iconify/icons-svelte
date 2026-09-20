<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxz09hbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxz09hbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowdstrike-dark" {...props}></Icon>
