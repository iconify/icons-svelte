<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-z-z9x6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-z-z9x6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:italic-filled" {...props}></Icon>
