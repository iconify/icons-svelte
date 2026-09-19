<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-64gvbsn.css';
import '../../css/p/pb7wd1b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-64gvbsn"/><path class="pb7wd1b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-cog-filled" {...props}></Icon>
