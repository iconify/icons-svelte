<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc1jzc-4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cc1jzc-4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:outdent-16-solid" {...props}></Icon>
