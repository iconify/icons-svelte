<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi2hnbb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2hnbb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radiation-fill-round" {...props}></Icon>
