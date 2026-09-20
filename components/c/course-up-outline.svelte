<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic18gdbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic18gdbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:course-up-outline" {...props}></Icon>
