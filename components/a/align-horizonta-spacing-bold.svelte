<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqlxk4byx.css';
import '../../css/g/gxoky2bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqlxk4byx"/><path class="gxoky2bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizonta-spacing-bold" {...props}></Icon>
