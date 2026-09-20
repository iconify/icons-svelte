<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz6c3ccrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yz6c3ccrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-down-16" {...props}></Icon>
