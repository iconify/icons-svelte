<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjjbun7en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xjjbun7en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:badge-16-solid" {...props}></Icon>
