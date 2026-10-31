<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beh9hpboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beh9hpboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:keyframes-round" {...props}></Icon>
