<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8j73eh3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8j73eh3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:option" {...props}></Icon>
