<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zie6h6bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zie6h6bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-triangle-solid" {...props}></Icon>
