<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f69_d7b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f69_d7b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pixiv-dark" {...props}></Icon>
