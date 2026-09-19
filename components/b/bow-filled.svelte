<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv9e3f4va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv9e3f4va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bow-filled" {...props}></Icon>
