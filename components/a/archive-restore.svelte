<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-x4nib5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-x4nib5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:archive-restore" {...props}></Icon>
