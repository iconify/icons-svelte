<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih4kqxb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih4kqxb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-plus" {...props}></Icon>
