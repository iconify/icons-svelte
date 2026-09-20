<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1xwzvbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g1xwzvbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:gift-filled" {...props}></Icon>
