<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_qhlmp2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_qhlmp2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-outline" {...props}></Icon>
