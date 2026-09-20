<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6etxabwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6etxabwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:form-outline" {...props}></Icon>
