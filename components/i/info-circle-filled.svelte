<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e17yj__7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e17yj__7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:info-circle-filled" {...props}></Icon>
