<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k961ckbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k961ckbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:order-book-48" {...props}></Icon>
