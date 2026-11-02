<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp9b9bcbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp9b9bcbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parfum-fill" {...props}></Icon>
