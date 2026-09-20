<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x486k7kau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x486k7kau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-filled" {...props}></Icon>
