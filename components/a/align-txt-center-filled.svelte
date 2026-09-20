<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1t-cvl_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l1t-cvl_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:align-txt-center-filled" {...props}></Icon>
