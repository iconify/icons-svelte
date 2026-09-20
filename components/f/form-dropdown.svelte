<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftk_62bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftk_62bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:form-dropdown" {...props}></Icon>
