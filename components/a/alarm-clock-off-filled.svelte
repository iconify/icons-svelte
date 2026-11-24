<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weapb9upb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weapb9upb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:alarm-clock-off-filled" {...props}></Icon>
