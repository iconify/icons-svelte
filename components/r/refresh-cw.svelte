<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w38dn7b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w38dn7b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:refresh-cw" {...props}></Icon>
