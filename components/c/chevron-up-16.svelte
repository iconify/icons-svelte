<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grn6zs_cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="grn6zs_cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-up-16" {...props}></Icon>
