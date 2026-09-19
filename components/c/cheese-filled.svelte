<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgh1gibyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgh1gibyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cheese-filled" {...props}></Icon>
