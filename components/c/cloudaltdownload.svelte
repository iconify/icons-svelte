<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp2mkxbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="kp2mkxbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudaltdownload" {...props}></Icon>
