<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kra7neb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":758};
const content = `<path class="kra7neb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bell" {...props}></Icon>
