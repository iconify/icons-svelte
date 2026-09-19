<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl2-epb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl2-epb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-7-filled" {...props}></Icon>
