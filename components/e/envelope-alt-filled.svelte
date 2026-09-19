<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x072svvsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x072svvsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:envelope-alt-filled" {...props}></Icon>
