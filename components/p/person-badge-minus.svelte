<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdk_v4oev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wdk_v4oev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-badge-minus" {...props}></Icon>
