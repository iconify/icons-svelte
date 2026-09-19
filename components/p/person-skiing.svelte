<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvm5bl8qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wvm5bl8qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-skiing" {...props}></Icon>
