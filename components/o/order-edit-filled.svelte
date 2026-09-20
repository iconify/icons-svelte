<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtmq0gbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mtmq0gbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-edit-filled" {...props}></Icon>
