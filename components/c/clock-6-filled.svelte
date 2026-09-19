<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_5tktevv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_5tktevv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-6-filled" {...props}></Icon>
