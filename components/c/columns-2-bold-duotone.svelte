<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za9uchb8f.css';
import '../../css/j/j2-x-cbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za9uchb8f"/><path class="j2-x-cbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-2-bold-duotone" {...props}></Icon>
