<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls1_ug9iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls1_ug9iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reply-circle" {...props}></Icon>
