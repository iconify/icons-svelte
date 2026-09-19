<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxw1mmmpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="oxw1mmmpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hockey" {...props}></Icon>
