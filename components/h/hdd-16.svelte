<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i39u7r_ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i39u7r_ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hdd-16" {...props}></Icon>
