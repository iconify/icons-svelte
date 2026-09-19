<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flug27b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flug27b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-shield-filled" {...props}></Icon>
