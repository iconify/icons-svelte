<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b13icbc7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b13icbc7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bug-outline" {...props}></Icon>
