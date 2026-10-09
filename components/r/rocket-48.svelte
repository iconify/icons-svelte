<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-v249b3a.css';
import '../../css/u/uljwuewwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k-v249b3a"/><path class="uljwuewwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rocket-48" {...props}></Icon>
