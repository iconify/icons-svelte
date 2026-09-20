<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e65x3t4hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e65x3t4hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:cancel" {...props}></Icon>
