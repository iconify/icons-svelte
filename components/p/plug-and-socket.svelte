<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-iz-12dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o-iz-12dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:plug-and-socket" {...props}></Icon>
