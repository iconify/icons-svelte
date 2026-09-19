<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpkw_81oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hpkw_81oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cake-16-solid" {...props}></Icon>
