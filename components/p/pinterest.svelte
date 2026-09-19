<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de85xv_ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1025};
const content = `<path class="de85xv_ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pinterest" {...props}></Icon>
