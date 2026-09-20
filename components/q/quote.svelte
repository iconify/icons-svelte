<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzuy0jr7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":9};
const content = `<path class="xzuy0jr7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:quote" {...props}></Icon>
