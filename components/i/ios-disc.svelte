<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxx4v7bby.css';
import '../../css/s/snz1cvidd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxx4v7bby"/><path class="snz1cvidd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-disc" {...props}></Icon>
