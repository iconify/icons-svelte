<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xka1fh12u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xka1fh12u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-kanban" {...props}></Icon>
