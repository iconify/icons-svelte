<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhu4i3sbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bhu4i3sbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-stack-16-solid" {...props}></Icon>
