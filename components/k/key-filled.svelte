<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4t5k-aiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4t5k-aiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:key-filled" {...props}></Icon>
