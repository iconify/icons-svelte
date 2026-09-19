<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emfxp9bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emfxp9bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:link-circle-02" {...props}></Icon>
