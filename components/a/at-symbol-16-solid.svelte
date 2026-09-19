<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqedgs0ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zqedgs0ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:at-symbol-16-solid" {...props}></Icon>
