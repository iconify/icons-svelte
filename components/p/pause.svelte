<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzhw3vcys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzhw3vcys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pause" {...props}></Icon>
