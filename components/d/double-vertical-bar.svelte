<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9zt39bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a9zt39bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:double-vertical-bar" {...props}></Icon>
