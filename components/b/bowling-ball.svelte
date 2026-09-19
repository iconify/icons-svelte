<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhfrh6b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qhfrh6b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bowling-ball" {...props}></Icon>
