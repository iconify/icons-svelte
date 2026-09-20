<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw98_2wjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pw98_2wjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:adjust-width-filled" {...props}></Icon>
