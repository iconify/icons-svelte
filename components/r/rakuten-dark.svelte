<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sydg7eklb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sydg7eklb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rakuten-dark" {...props}></Icon>
