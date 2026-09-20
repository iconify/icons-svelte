<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p220ddb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p220ddb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opnform-dark" {...props}></Icon>
