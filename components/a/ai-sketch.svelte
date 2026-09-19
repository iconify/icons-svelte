<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aucau2adi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aucau2adi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-sketch" {...props}></Icon>
