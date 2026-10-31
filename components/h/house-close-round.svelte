<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck_qurr6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_qurr6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-close-round" {...props}></Icon>
