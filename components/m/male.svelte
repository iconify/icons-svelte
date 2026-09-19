<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhw-b4bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="qhw-b4bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:male" {...props}></Icon>
