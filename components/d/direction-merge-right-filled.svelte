<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enpo_vbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="enpo_vbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-merge-right-filled" {...props}></Icon>
