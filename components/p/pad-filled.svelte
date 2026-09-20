<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqpcls_me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jqpcls_me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pad-filled" {...props}></Icon>
