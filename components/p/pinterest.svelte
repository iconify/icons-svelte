<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr00bhowv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="nr00bhowv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:pinterest" {...props}></Icon>
