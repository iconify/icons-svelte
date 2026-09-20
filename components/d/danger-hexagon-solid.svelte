<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2lxpi_vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2lxpi_vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-hexagon-solid" {...props}></Icon>
