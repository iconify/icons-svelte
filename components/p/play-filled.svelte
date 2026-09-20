<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqp4cw_dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nqp4cw_dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:play-filled" {...props}></Icon>
