<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2ib5fbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2ib5fbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-edit-outline" {...props}></Icon>
