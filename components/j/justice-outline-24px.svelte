<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arszavy-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="arszavy-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:justice-outline-24px" {...props}></Icon>
