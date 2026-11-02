<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa1gi8eew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa1gi8eew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:profile-2-fill" {...props}></Icon>
