<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceau6_uqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceau6_uqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edge-new-fill" {...props}></Icon>
