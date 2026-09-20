<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbv_j9a6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbv_j9a6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eljueves" {...props}></Icon>
