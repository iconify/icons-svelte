<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3stezyor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3stezyor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:find-replace-line" {...props}></Icon>
