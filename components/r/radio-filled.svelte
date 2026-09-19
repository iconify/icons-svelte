<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eetpvy9gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eetpvy9gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:radio-filled" {...props}></Icon>
