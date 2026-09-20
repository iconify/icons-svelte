<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_w473vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vd_w473vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:field-16" {...props}></Icon>
