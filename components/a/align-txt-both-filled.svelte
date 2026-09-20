<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnd6xk9ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qnd6xk9ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:align-txt-both-filled" {...props}></Icon>
