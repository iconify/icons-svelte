<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdqx10g5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdqx10g5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rollback-filled" {...props}></Icon>
