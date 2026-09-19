<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx_j74_gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mx_j74_gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-return-right" {...props}></Icon>
