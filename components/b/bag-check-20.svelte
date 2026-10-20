<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gahgzf5qd.css';
import '../../css/e/e55zwmb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gahgzf5qd"/><path class="e55zwmb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-check-20" {...props}></Icon>
